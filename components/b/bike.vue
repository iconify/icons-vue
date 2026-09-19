<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/y/ylhx5jbuy.css';
import '../../css/k/kp6x66biy.css';
import '../../css/r/rp-5i7zrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ylhx5jbuy"/><path class="kp6x66biy"/><path class="rp-5i7zrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bike" /></template>
