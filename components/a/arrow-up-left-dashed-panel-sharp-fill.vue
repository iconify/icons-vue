<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bto42ybcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bto42ybcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-left-dashed-panel-sharp-fill" /></template>
