<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us80zob-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us80zob-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:diamond" /></template>
