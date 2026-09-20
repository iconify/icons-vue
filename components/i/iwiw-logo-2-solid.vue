<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up_032bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="up_032bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:iwiw-logo-2-solid" /></template>
