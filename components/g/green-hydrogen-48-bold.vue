<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_ra3nchf.css';
import '../../css/e/esw8pgb2a.css';
import '../../css/l/ld5dtibtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w_ra3nchf"/><path class="esw8pgb2a"/><path class="ld5dtibtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-hydrogen-48-bold" /></template>
