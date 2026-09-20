<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmwmrlbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tmwmrlbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:fingerprint-2-flat" /></template>
