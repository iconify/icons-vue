<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r24r7qt7r.css';
import '../../css/x/xuu2b7bwb.css';
import '../../css/c/ct_c29f3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r24r7qt7r"/><path class="xuu2b7bwb"/><path class="ct_c29f3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drone-inspection-20" /></template>
