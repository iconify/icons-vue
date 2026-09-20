<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd05r9bdf.css';
import '../../css/k/k0hxhqbwo.css';
import '../../css/r/ralef_bab.css';
import '../../css/z/zqhekobbq.css';
import '../../css/h/hb1lhlb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bd05r9bdf"/><path class="k0hxhqbwo"/><circle class="ralef_bab"/><path class="zqhekobbq"/><path class="hb1lhlb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:figma" /></template>
