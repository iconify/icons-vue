<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkoq81btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="xkoq81btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-fire-extinguisher" /></template>
