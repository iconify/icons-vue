<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wy0kmte2f.css';
import '../../css/d/df-j23bjo.css';
import '../../css/b/bh-7c2_ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wy0kmte2f"/><path class="df-j23bjo"/><path class="bh-7c2_ml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-lock-02" /></template>
