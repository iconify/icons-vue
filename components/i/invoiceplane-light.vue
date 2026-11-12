<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/raj4z-pfe.css';
import '../../css/l/lx0j_nfbx.css';
import '../../css/i/iyxxnubym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="raj4z-pfe"/><path class="lx0j_nfbx"/><path class="iyxxnubym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoiceplane-light" /></template>
