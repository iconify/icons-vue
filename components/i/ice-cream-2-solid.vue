<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fppgpssoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fppgpssoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ice-cream-2-solid" /></template>
