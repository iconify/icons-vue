<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2_w79bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o2_w79bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:align-right" /></template>
