<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm2_xkwlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm2_xkwlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cash-multiple" /></template>
