<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2c492bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r2c492bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bed-pulse" /></template>
