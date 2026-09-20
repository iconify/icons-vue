<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjkax8bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjkax8bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:about-me-logo" /></template>
