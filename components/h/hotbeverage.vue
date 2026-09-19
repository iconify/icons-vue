<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzpan3bci.css';
import '../../css/o/ovgcn15iq.css';
import '../../css/k/kw6ok-jlw.css';
import '../../css/c/cforkdjpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pzpan3bci"/><path class="ovgcn15iq"/><path class="kw6ok-jlw"/><path class="cforkdjpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:hotbeverage" /></template>
