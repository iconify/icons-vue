<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/s/szxt87bjn.css';
import '../../css/q/qj8iipbgi.css';
import '../../css/d/d-2r4nbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="szxt87bjn"/><path class="qj8iipbgi"/><path clip-rule="evenodd" class="d-2r4nbvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-sharp-duotone" /></template>
