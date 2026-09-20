<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy6nsxr8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy6nsxr8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chart-2-filled" /></template>
