<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wksup-1_p.css';
import '../../css/r/r0_9jbcny.css';
import '../../css/w/wcmprwboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wksup-1_p"/><path class="r0_9jbcny"/><path class="wcmprwboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:es-pv-1x1" /></template>
