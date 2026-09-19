<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqqot8bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqqot8bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-ps-2014" /></template>
