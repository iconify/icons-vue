<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwk4867sm.css';
import '../../css/n/n7yph_i7l.css';
import '../../css/q/qr-5js_2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mwk4867sm"/><path class="n7yph_i7l"/><path class="qr-5js_2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kchat-dark" /></template>
