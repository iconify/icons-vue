<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amlldccry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="amlldccry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:empty-clipboard-solid" /></template>
