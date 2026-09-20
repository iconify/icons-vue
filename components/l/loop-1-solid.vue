<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucgsgdbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ucgsgdbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:loop-1-solid" /></template>
