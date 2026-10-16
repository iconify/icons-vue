<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdtcojbje.css';
import '../../css/p/pycxazbfr.css';
import '../../css/e/eepo9qbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hdtcojbje"/><path class="pycxazbfr"/><path class="eepo9qbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:containment-dome-20" /></template>
