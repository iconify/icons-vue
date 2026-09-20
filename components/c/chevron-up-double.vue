<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue_x4m1-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ue_x4m1-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:chevron-up-double" /></template>
