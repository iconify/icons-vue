<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcv5y0bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="dcv5y0bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:fire-alt" /></template>
