<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubo9a1bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ubo9a1bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:eclipse-ide-logo-solid" /></template>
