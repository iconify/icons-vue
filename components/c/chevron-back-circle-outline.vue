<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-tflgzje.css';
import '../../css/w/wv95f72ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-tflgzje"/><path class="wv95f72ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chevron-back-circle-outline" /></template>
