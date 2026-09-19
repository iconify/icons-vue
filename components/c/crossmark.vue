<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntm3w5bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ntm3w5bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:crossmark" /></template>
