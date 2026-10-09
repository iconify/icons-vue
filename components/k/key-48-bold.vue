<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umhq261qv.css';
import '../../css/g/gf_wrnomr.css';
import '../../css/p/p5jrx9s3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="umhq261qv"/><path class="gf_wrnomr"/><path class="p5jrx9s3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-48-bold" /></template>
