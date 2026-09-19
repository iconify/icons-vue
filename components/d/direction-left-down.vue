<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0273qbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0273qbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:direction-left-down" /></template>
