<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/eukozub-p.css';
import '../../css/t/tnbv3bc-m.css';
import '../../css/j/j1g38rb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="eukozub-p"/><path class="tnbv3bc-m"/><path class="j1g38rb7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lock-key" /></template>
