<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iimbzfbkb.css';
import '../../css/l/l1vx45b4j.css';
import '../../css/g/gj_hcxo9i.css';
import '../../css/y/y75vuqbzr.css';
import '../../css/w/wzqr6d1pg.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iimbzfbkb"/><path class="l1vx45b4j"/><path class="gj_hcxo9i"/><path class="y75vuqbzr"/><path class="wzqr6d1pg"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:balcony-solar-20" /></template>
