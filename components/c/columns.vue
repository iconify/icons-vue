<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-o3-66fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b-o3-66fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:columns" /></template>
