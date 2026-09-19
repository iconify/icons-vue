<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmx2n3bsv.css';
import '../../css/k/k0e30mbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lmx2n3bsv"/><path class="k0e30mbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:exit-to-app" /></template>
