<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up54fzbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="up54fzbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:c-language-logo-block" /></template>
