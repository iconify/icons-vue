<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnypmy.css';
import '../../css/a/a0m25c.css';
import '../../css/o/oq600w.css';
import '../../css/s/sdwher.css';
import '../../css/j/j_b-yc.css';
import '../../css/j/juj32z.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-16.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnypmy"/><path class="a0m25c oq600w"/><path class="a0m25c sdwher"/><path class="a0m25c j_b-yc"/><path class="a0m25c juj32z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:home-md-alt-twotone" /></template>
