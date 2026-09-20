<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i59_vpbwp.css';
import '../../css/c/cmhxciomr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i59_vpbwp"/><path class="cmhxciomr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:app-window-multiple-bold" /></template>
