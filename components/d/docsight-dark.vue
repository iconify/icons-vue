<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvjyobsxa.css';
import '../../css/m/mdf334osa.css';
import '../../css/n/ng8zrebtc.css';
import '../../css/k/k565abc4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xvjyobsxa"/><path class="mdf334osa"/><path class="ng8zrebtc"/><circle class="k565abc4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docsight-dark" /></template>
