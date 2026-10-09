<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f68_4fg2y.css';
import '../../css/m/mnnp_abay.css';
import '../../css/x/xscus6cad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f68_4fg2y"/><path class="mnnp_abay"/><path class="xscus6cad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cooking-pot-20" /></template>
