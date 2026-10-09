<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yozhcqskc.css';
import '../../css/t/tkfpxusan.css';
import '../../css/y/y9re-u6qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yozhcqskc"/><path class="tkfpxusan"/><path class="y9re-u6qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cube-20-bold" /></template>
