<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm_qsybka.css';
import '../../css/v/vdkkambso.css';
import '../../css/v/vy8kcme0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm_qsybka"/><path class="vdkkambso"/><path class="vy8kcme0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-happy-heart-eyes" /></template>
