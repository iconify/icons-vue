<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7fr20m4o.css';
import '../../css/g/g6shwtddl.css';
import '../../css/q/q8u0wn3hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e7fr20m4o"/><path class="g6shwtddl"/><path class="q8u0wn3hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:dk-1x1" /></template>
