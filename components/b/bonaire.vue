<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy7879nbj.css';
import '../../css/k/kp6rhw96h.css';
import '../../css/w/waq7j53kz.css';
import '../../css/v/va2xzgb_k.css';
import '../../css/b/btl0gxbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="wy7879nbj"/><path class="kp6rhw96h"/><path class="waq7j53kz"/><path class="va2xzgb_k"/><path class="btl0gxbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:bonaire" /></template>
