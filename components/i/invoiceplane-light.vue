<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2jubac4c.css';
import '../../css/h/hydjcxbrq.css';
import '../../css/i/iyxxnubym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2jubac4c"/><path class="hydjcxbrq"/><path class="iyxxnubym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoiceplane-light" /></template>
