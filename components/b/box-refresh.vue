<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3w13jb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3w13jb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-refresh" /></template>
