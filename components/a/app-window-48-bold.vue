<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrk88uxja.css';
import '../../css/q/qt2057bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qrk88uxja"/><path class="qt2057bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:app-window-48-bold" /></template>
