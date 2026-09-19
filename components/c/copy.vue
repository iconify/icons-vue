<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnztqcbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":480};
const content = `<path class="vnztqcbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:copy" /></template>
