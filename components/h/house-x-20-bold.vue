<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuveebb1b.css';
import '../../css/z/ziroa4b5h.css';
import '../../css/d/dz0fjhb9o.css';
import '../../css/c/cejnnhkdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zuveebb1b"/><path class="ziroa4b5h"/><path class="dz0fjhb9o"/><path class="cejnnhkdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-x-20-bold" /></template>
