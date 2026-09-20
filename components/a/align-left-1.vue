<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0esbbubm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0esbbubm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:align-left-1" /></template>
