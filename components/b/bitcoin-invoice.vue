<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pv6pnyb6o.css';
import '../../css/k/kgn4sjj3u.css';
import '../../css/g/gd4jaw5nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pv6pnyb6o"/><path class="kgn4sjj3u"/><path class="gd4jaw5nf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bitcoin-invoice" /></template>
