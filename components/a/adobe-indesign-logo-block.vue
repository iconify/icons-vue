<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxb47rbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fxb47rbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-indesign-logo-block" /></template>
