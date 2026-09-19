<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/sbrjebj6j.css';
import '../../css/l/luo1b9d3l.css';
import '../../css/d/dnpvs6bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="sbrjebj6j"/><path class="luo1b9d3l"/><path class="dnpvs6bkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-block-02" /></template>
