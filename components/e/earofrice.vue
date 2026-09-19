<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly_b0dbrd.css';
import '../../css/j/joidnyzty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ly_b0dbrd"/><path class="joidnyzty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:earofrice" /></template>
