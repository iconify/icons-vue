<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvnl4tf6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvnl4tf6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-pull-request-arrow" /></template>
