<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_i17xbai.css';
import '../../css/l/llov8mbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_i17xbai"/><path class="llov8mbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-terminal-filled" /></template>
