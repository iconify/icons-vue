<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej5bhbbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ej5bhbbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:magento-logo-block" /></template>
