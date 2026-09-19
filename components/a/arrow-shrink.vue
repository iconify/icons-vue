<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pim-13nez.css';
import '../../css/h/hx4043pqx.css';
import '../../css/v/vrd74fvzf.css';
import '../../css/m/mwl5gsbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pim-13nez"/><path class="hx4043pqx"/><path class="vrd74fvzf"/><path class="mwl5gsbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-shrink" /></template>
