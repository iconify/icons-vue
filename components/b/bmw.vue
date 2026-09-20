<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rafsg0atz.css';
import '../../css/w/wn36-3bgk.css';
import '../../css/k/k7_ztobeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rafsg0atz"/><path class="wn36-3bgk"/><path class="k7_ztobeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bmw" /></template>
