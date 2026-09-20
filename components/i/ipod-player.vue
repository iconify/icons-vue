<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lekja6r0i.css';
import '../../css/m/mwjzc-b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lekja6r0i"/><path class="mwjzc-b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:ipod-player" /></template>
