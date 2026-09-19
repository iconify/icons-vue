<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et-jf20mo.css';
import '../../css/a/a9s0llb_c.css';
import '../../css/d/dthcxeb8v.css';
import '../../css/k/k-p4f3sbw.css';
import '../../css/x/xc31xiz5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="et-jf20mo"/><path class="a9s0llb_c"/><path class="dthcxeb8v"/><path class="k-p4f3sbw"/><path class="xc31xiz5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:frontfacingchick" /></template>
