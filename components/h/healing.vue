<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjkthvsjg.css';
import '../../css/q/qu789qgwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cjkthvsjg"/><path class="qu789qgwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:healing" /></template>
