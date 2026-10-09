<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp-8xbcar.css';
import '../../css/s/sw1rf8b4b.css';
import '../../css/b/b3fhqxbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mp-8xbcar"/><path class="sw1rf8b4b"/><path class="b3fhqxbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:circuit-breaker-48" /></template>
