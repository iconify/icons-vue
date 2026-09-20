<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6kjkhvlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6kjkhvlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:ffffounding-logo-solid" /></template>
