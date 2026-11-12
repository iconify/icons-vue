<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/legs_-oed.css';
import '../../css/n/ny5b9ebqn.css';
import '../../css/n/n7g6991ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="legs_-oed"/><path class="ny5b9ebqn"/><path class="n7g6991ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-swisstransfer-dark" /></template>
