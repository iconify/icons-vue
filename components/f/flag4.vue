<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie766ibcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie766ibcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:flag4" /></template>
