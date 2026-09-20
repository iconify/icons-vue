<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igi6jx_0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="igi6jx_0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:gowalla-logo-3-solid" /></template>
