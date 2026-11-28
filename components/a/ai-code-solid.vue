<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwywovojx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwywovojx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-code-solid" /></template>
