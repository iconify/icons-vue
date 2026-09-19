<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m39lfrbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m39lfrbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:long-bottom-down" /></template>
