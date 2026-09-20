<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pri68xb4e.css';
import '../../css/i/i2a0yabqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pri68xb4e"/><path class="i2a0yabqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cal-com-dark" /></template>
