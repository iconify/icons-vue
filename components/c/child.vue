<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asca-eb-n.css';
import '../../css/k/k2a66hndc.css';
import '../../css/x/xcyaqlbxm.css';
import '../../css/c/cexd8ehxg.css';
import '../../css/c/cpuyfc2bi.css';
import '../../css/f/foygk1awv.css';
import '../../css/l/lcau_6b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="asca-eb-n"/><path class="k2a66hndc"/><path class="xcyaqlbxm"/><path class="cexd8ehxg"/><path class="cpuyfc2bi"/><path class="foygk1awv"/><path class="lcau_6b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:child" /></template>
