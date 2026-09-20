<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb4qzoycs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mb4qzoycs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:deezer-logo-solid" /></template>
