<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf_0_vbwb.css';
import '../../css/p/pxc5p1dyz.css';
import '../../css/n/ng4ifmbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xf_0_vbwb"/><path class="pxc5p1dyz"/><path class="ng4ifmbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:compost-20-bold" /></template>
