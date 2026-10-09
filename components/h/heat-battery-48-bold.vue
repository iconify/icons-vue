<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxmtgk7_c.css';
import '../../css/e/el25l0wwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uxmtgk7_c"/><path class="el25l0wwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-battery-48-bold" /></template>
