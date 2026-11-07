<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgs-libjk.css';
import '../../css/o/oam048mkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgs-libjk"/><path class="oam048mkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-heart-bold" /></template>
