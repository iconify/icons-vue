<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsc0ufgkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsc0ufgkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:apple-keyboard-shift" /></template>
