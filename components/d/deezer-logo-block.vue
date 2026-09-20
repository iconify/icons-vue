<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgj48d40s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgj48d40s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:deezer-logo-block" /></template>
