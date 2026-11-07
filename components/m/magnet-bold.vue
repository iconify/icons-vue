<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crd2je-4i.css';
import '../../css/f/fxwwtlavh.css';
import '../../css/q/qkrmpnbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crd2je-4i"/><path class="fxwwtlavh"/><path class="qkrmpnbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnet-bold" /></template>
