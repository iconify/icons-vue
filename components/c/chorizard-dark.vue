<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_wo_pbay.css';
import '../../css/i/imad5bjrh.css';
import '../../css/x/xi-cb_bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j_wo_pbay"/><path class="imad5bjrh"/><path class="xi-cb_bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chorizard-dark" /></template>
