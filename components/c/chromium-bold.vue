<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei6qdubbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ei6qdubbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:chromium-bold" /></template>
