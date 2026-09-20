<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxfe_ublk.css';
import '../../css/u/u-5087bul.css';
import '../../css/y/yn4kitb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxfe_ublk"/><path class="u-5087bul"/><path clip-rule="evenodd" class="yn4kitb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:gauge-1" /></template>
