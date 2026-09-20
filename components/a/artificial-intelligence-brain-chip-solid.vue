<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/belk3o3_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="belk3o3_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:artificial-intelligence-brain-chip-solid" /></template>
