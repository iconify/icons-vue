<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2w919zsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2w919zsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-right-dashed-panel" /></template>
