<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/irxymccfj.css';
import '../../css/k/khfhn220m.css';
import '../../css/m/mfkoxfbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="irxymccfj"/><path class="khfhn220m"/><path class="mfkoxfbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:exchange-bitcoin" /></template>
