<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pj4bklnkf.css';
import '../../css/e/eepjeibon.css';
import '../../css/e/e9polmbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pj4bklnkf"/><path class="eepjeibon"/><path class="e9polmbot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:car-battery-bold" /></template>
