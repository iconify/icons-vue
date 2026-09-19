<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f03viiyfk.css';
import '../../css/u/ux3cgkxqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f03viiyfk"/><path class="ux3cgkxqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-server" /></template>
