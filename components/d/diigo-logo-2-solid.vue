<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu3-adbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eu3-adbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:diigo-logo-2-solid" /></template>
