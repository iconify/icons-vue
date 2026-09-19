<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u2ffjhxgz.css';
import '../../css/b/bgh9y3bsn.css';
import '../../css/l/lsle5sbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="u2ffjhxgz"/><path class="bgh9y3bsn"/><path class="lsle5sbqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lock-keyhole-open" /></template>
