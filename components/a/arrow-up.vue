<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw6aov9hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nw6aov9hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:arrow-up" /></template>
