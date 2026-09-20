<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvc4pqvny.css';
import '../../css/k/kmd5mubrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qvc4pqvny"/><path class="kmd5mubrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-calendar-date" /></template>
