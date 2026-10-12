<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8oy8xbju.css';
import '../../css/i/i3509_9wg.css';
import '../../css/r/rro8xm0eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m8oy8xbju"/><path class="i3509_9wg"/><path class="rro8xm0eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:abacus-48-bold" /></template>
