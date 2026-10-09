<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt4t1kbqx.css';
import '../../css/x/x-k2aqbil.css';
import '../../css/z/zd6bbv0yb.css';
import '../../css/y/yklljhbfl.css';
import '../../css/h/hs4lzx5nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lt4t1kbqx"/><path class="x-k2aqbil"/><path class="zd6bbv0yb"/><path class="yklljhbfl"/><path class="hs4lzx5nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charging-hub-20-bold" /></template>
