<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnix5mb_n.css';
import '../../css/f/fvm61b_7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pnix5mb_n"/><path class="fvm61b_7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ackify" /></template>
