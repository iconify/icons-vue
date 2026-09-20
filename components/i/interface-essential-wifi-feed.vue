<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnsha0bgv.css';
import '../../css/g/gol1xybds.css';
import '../../css/c/czudsiv_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lnsha0bgv"/><path class="gol1xybds"/><path class="czudsiv_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-wifi-feed" /></template>
