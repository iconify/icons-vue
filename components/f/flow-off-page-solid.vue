<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxl-5499g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxl-5499g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-off-page-solid" /></template>
