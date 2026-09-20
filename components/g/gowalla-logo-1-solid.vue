<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llf52oz0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="llf52oz0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:gowalla-logo-1-solid" /></template>
