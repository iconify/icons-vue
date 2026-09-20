<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9eu28bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d9eu28bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:check-solid" /></template>
