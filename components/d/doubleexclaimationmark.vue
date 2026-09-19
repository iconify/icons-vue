<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox8i1rs_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ox8i1rs_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:doubleexclaimationmark" /></template>
