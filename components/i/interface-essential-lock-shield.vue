<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgcl_acrx.css';
import '../../css/n/n83ma-b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jgcl_acrx"/><path class="n83ma-b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-lock-shield" /></template>
