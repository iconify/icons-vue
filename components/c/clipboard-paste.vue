<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bporwpv9i.css';
import '../../css/u/ujw8tpbuy.css';
import '../../css/c/cbby56vwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bporwpv9i"/><path class="ujw8tpbuy"/><path class="cbby56vwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:clipboard-paste" /></template>
