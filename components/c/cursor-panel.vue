<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv5mrgn9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv5mrgn9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-panel" /></template>
