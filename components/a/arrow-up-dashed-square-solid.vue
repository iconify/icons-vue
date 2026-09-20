<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og2kr9jnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="og2kr9jnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-up-dashed-square-solid" /></template>
