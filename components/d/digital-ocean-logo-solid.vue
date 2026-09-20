<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmpx7kb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmpx7kb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:digital-ocean-logo-solid" /></template>
