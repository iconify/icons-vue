<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js93vwb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="js93vwb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:line-app-logo-block" /></template>
