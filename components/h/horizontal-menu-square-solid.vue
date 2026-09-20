<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fztv_-b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fztv_-b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:horizontal-menu-square-solid" /></template>
