<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i45v7jx2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i45v7jx2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:desktop-help-solid" /></template>
