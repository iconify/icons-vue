<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6ajr_bsq.css';
import '../../css/u/ufvpeacwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="f6ajr_bsq"/><path clip-rule="evenodd" class="ufvpeacwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-right-circle" /></template>
