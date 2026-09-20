<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swb92wcvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="swb92wcvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:code-climate-logo-block" /></template>
