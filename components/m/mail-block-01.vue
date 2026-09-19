<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t18islbco.css';
import '../../css/m/mz8pfhblh.css';
import '../../css/d/dnpvs6bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="t18islbco"/><path class="mz8pfhblh"/><path class="dnpvs6bkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-block-01" /></template>
