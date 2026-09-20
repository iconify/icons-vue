<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_b0erywf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="s_b0erywf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:lift-gate-10" /></template>
