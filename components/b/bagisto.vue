<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffpnvgb5x.css';
import '../../css/k/kozsj6bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ffpnvgb5x"/><path class="kozsj6bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bagisto" /></template>
