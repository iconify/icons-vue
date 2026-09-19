<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvfx0dbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvfx0dbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:bold" /></template>
