<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_pc-t0wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c_pc-t0wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:magic" /></template>
