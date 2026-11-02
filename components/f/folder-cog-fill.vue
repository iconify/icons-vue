<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imzn-ib-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imzn-ib-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-cog-fill" /></template>
