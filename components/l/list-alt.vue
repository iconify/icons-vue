<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6p5ah1gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e6p5ah1gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:list-alt" /></template>
