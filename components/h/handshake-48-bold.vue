<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5mm6ob9l.css';
import '../../css/c/cru7ppb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w5mm6ob9l"/><path class="cru7ppb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:handshake-48-bold" /></template>
