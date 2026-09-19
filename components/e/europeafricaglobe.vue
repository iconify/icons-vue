<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzofhbcwo.css';
import '../../css/o/ow7bebbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lzofhbcwo"/><path class="ow7bebbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:europeafricaglobe" /></template>
