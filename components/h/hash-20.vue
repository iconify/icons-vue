<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq0_hgb3f.css';
import '../../css/v/vxl90jbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kq0_hgb3f"/><path class="vxl90jbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hash-20" /></template>
