<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_di7u-yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_di7u-yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:align-text-center-solid" /></template>
