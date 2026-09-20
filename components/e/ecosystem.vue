<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msnkf_bkn.css';
import '../../css/k/kq5sxkbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="msnkf_bkn"/><path class="kq5sxkbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:ecosystem" /></template>
