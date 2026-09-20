<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-mridb4l.css';
import '../../css/i/inzdek_cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="m-mridb4l"/><path class="inzdek_cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:comments" /></template>
