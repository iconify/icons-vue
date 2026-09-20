<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yab7w5bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yab7w5bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-arrows-up-left" /></template>
