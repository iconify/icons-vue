<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gycplyitt.css';
import '../../css/s/snq7lfbcd.css';
import '../../css/t/t83hz6hkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gycplyitt"/><path class="snq7lfbcd wm-shadow"/><path class="t83hz6hkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:command-engrave" /></template>
