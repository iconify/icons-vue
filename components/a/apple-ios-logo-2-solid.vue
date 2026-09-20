<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og8okim2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="og8okim2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:apple-ios-logo-2-solid" /></template>
