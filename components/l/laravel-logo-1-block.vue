<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7mt03btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q7mt03btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:laravel-logo-1-block" /></template>
