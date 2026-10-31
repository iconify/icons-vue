<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lv7116bbl.css';
import '../../css/t/teu-s7guz.css';
import '../../css/l/lfoy-8bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lv7116bbl wm-shadow"/><path class="teu-s7guz wm-shadow"/><path class="lfoy-8bug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:bitcoin" /></template>
