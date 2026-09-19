<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8n63d11k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="f8n63d11k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:logo-windows" /></template>
