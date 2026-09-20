<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqby38bfg.css';
import '../../css/u/uzk27_m6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqby38bfg"/><path class="uzk27_m6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:calculator-1" /></template>
