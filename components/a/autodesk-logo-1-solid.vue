<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4riv7b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w4riv7b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:autodesk-logo-1-solid" /></template>
