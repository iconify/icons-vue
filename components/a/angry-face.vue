<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxary8a8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vxary8a8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:angry-face" /></template>
