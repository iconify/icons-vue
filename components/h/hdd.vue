<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/ak99b7bpx.css';
import '../../css/w/wstwwib_m.css';
import '../../css/t/t65iejbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ak99b7bpx"/><path class="wstwwib_m"/><path class="t65iejbne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hdd" /></template>
