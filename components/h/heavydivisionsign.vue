<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rywc8nbcc.css';
import '../../css/m/mh7spwbcm.css';
import '../../css/l/lzxnqd56o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rywc8nbcc"/><circle class="mh7spwbcm"/><circle class="lzxnqd56o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:heavydivisionsign" /></template>
