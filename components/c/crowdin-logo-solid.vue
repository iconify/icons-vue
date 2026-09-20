<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjjqoz9le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fjjqoz9le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:crowdin-logo-solid" /></template>
