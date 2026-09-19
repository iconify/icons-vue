<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxl5vd-_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hxl5vd-_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-box-fill-12" /></template>
