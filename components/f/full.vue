<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssduyhgbk.css';
import '../../css/k/ktcdaovuf.css';
import '../../css/m/mwuopsbdz.css';
import '../../css/v/v2j0phshp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssduyhgbk"/><path class="ktcdaovuf"/><path class="mwuopsbdz"/><path class="v2j0phshp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:full" /></template>
