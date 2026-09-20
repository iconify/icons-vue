<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i225lr4ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i225lr4ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:horizontal-toggle-button-solid" /></template>
