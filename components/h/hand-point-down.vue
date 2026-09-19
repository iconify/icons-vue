<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfzdz_hbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mfzdz_hbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:hand-point-down" /></template>
