<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q51zeztgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q51zeztgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-p-box" /></template>
