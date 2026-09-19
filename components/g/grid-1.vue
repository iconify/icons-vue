<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/h/hu98blb9x.css';
import '../../css/n/nnw9klbar.css';
import '../../css/i/i2cyzso1p.css';
import '../../css/g/g0zg1fb3v.css';
import '../../css/i/i9i-98bne.css';
import '../../css/w/wu7ugqaks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="gopnm44um"><rect class="hu98blb9x"/><rect class="nnw9klbar"/><rect class="i2cyzso1p"/><rect class="g0zg1fb3v"/><rect class="i9i-98bne"/><rect class="wu7ugqaks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:grid-1" /></template>
