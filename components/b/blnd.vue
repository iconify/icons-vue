<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esc2lymja.css';
import '../../css/n/nn1p_hz4s.css';
import '../../css/w/w30ikw3fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esc2lymja"/><path class="nn1p_hz4s"/><path class="w30ikw3fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:blnd" /></template>
