<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/h/h06k64bje.css';
import '../../css/g/gdem_rh5e.css';
import '../../css/w/w487obc3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="h06k64bje"/><path class="gdem_rh5e"/><path class="w487obc3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:kiss-wink-heart" /></template>
