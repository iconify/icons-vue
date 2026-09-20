<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvux9ccjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvux9ccjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:atom-variant" /></template>
