<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cygiloihl.css';
import '../../css/w/wc2xakonk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cygiloihl"/><path class="wc2xakonk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-discord" /></template>
