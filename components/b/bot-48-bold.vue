<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu1885bds.css';
import '../../css/x/x3viw0xpi.css';
import '../../css/z/zn1bmf10z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qu1885bds"/><path class="x3viw0xpi"/><path class="zn1bmf10z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bot-48-bold" /></template>
