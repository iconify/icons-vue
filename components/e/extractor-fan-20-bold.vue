<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6forwbcg.css';
import '../../css/h/hj8-m_b6a.css';
import '../../css/q/qe1z6cbje.css';
import '../../css/h/h94jzsbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h6forwbcg"/><path class="hj8-m_b6a"/><path class="qe1z6cbje"/><path class="h94jzsbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:extractor-fan-20-bold" /></template>
