<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjmd_m1pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjmd_m1pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:gdgt-logo-solid" /></template>
