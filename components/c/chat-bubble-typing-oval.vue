<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/w/w7ty8bc8g.css';
import '../../css/k/kltjcob_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="w7ty8bc8g"/><path class="kltjcob_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-bubble-typing-oval" /></template>
