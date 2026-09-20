<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byi03x_hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="byi03x_hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:feeder" /></template>
