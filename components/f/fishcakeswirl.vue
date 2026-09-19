<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny2sfabep.css';
import '../../css/n/nnbs2674t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ny2sfabep"/><path class="nnbs2674t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:fishcakeswirl" /></template>
