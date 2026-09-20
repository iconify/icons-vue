<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpxxqepyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpxxqepyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:google-chrome" /></template>
