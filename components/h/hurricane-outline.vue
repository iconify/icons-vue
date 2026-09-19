<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mq_nynmza.css';
import '../../css/q/q_udj0h0z.css';
import '../../css/x/x6w93yb_v.css';
import '../../css/v/vr_ysibut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mq_nynmza"/><path class="q_udj0h0z"/><path class="x6w93yb_v"/><path class="vr_ysibut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hurricane-outline" /></template>
