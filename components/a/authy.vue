<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnhwnduys.css';
import '../../css/h/hgfh0_gbr.css';
import '../../css/o/o-byg3jhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lnhwnduys"/><path class="hgfh0_gbr"/><path class="o-byg3jhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:authy" /></template>
