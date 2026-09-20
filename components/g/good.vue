<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncjysacrn.css';
import '../../css/h/hv--zic2y.css';
import '../../css/e/evb5kpc_i.css';
import '../../css/z/zdagr0b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="ncjysacrn"/><path class="hv--zic2y"/><circle class="evb5kpc_i"/><circle class="zdagr0b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:good" /></template>
