<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e2_10oj2l.css';
import '../../css/d/df-j23bjo.css';
import '../../css/o/or3ztp_qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e2_10oj2l"/><path class="df-j23bjo"/><path class="or3ztp_qk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-remove-02" /></template>
