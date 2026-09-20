<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wesomf70y.css';
import '../../css/s/s71mep88y.css';
import '../../css/v/v5aq_m_zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wesomf70y"/><path class="s71mep88y"/><path class="v5aq_m_zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-money-coin-currency" /></template>
