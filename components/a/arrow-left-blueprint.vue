<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/w/w2meg0bwg.css';
import '../../css/g/g2znv1bsm.css';
import '../../css/k/kpwyn7bfm.css';
import '../../css/m/mk_i2qzng.css';
import '../../css/k/ksxkx1bml.css';
import '../../css/l/lotyeabac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="w2meg0bwg wm-deco"/><path class="g2znv1bsm wm-deco"/><path class="kpwyn7bfm wm-k"/><path class="mk_i2qzng wm-a"/><path class="ksxkx1bml wm-k"/><path class="lotyeabac wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-left-blueprint" /></template>
