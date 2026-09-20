<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-_jb_bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-_jb_bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gamepad-circle-outline" /></template>
