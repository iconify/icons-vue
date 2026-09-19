<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bp_mm0bva.css';
import '../../css/z/z9edi6b_u.css';
import '../../css/c/cn4jivb8s.css';
import '../../css/u/uh6-p-5cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bp_mm0bva"/><circle class="z9edi6b_u"/><circle class="cn4jivb8s"/><circle class="uh6-p-5cm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart-bubble-01" /></template>
