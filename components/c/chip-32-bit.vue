<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbbtivbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbbtivbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chip-32-bit" /></template>
