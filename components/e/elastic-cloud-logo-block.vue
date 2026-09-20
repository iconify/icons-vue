<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djpkk9btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="djpkk9btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:elastic-cloud-logo-block" /></template>
