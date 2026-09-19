<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_sfyacvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_sfyacvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-chart-bar-outline" /></template>
