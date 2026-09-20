<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyj3mqs7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cyj3mqs7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:cinema-4d-logo-solid" /></template>
