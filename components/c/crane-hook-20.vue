<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-oonistw.css';
import '../../css/b/b9083lrix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n-oonistw"/><path class="b9083lrix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crane-hook-20" /></template>
