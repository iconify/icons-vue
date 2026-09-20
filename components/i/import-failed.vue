<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2qct1-zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p2qct1-zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:import-failed" /></template>
