<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbusism_o.css';
import '../../css/w/wg80aqv_q.css';
import '../../css/z/zc-n46vmj.css';
import '../../css/f/fujwj-hky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nbusism_o"/><path class="wg80aqv_q"/><path class="zc-n46vmj"/><path class="fujwj-hky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ceiling-fan-20" /></template>
