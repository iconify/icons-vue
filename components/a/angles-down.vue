<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubnxg2ces.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ubnxg2ces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:angles-down" /></template>
