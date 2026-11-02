<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh68hobsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh68hobsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:droplets-fill" /></template>
