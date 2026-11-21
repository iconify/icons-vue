<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qefm_s0ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qefm_s0ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-after-effects-dark" /></template>
