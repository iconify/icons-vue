<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxq650zlt.css';
import '../../css/b/b_ayuzlry.css';
import '../../css/q/q3czggb2v.css';
import '../../css/s/sxcnixb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mxq650zlt"/><path class="b_ayuzlry"/><path class="q3czggb2v"/><path class="sxcnixb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cargo-drone-20-bold" /></template>
