<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inw8n8b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inw8n8b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:double-arrow-down" /></template>
