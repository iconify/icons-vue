<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nls4zt4jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nls4zt4jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:emoji-ball" /></template>
