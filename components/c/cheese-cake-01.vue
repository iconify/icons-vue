<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/eep0cg56r.css';
import '../../css/g/gm9yycbjl.css';
import '../../css/p/pqqc-y78h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="eep0cg56r"/><path class="gm9yycbjl"/><path class="pqqc-y78h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cheese-cake-01" /></template>
