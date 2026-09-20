<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr0vqrbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vr0vqrbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:claris-logo-block" /></template>
