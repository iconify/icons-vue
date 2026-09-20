<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiat6mbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jiat6mbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:aim-logo-solid" /></template>
