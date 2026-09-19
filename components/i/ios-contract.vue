<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2_axxtyj.css';
import '../../css/l/le9wl1t5r.css';
import '../../css/h/how4y_5ly.css';
import '../../css/x/xyb0mqbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r2_axxtyj"/><path class="le9wl1t5r"/><path class="how4y_5ly"/><path class="xyb0mqbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-contract" /></template>
