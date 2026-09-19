<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy_h3mg2o.css';
import '../../css/t/t_zwr_bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="sy_h3mg2o"/><path transform="scale(.79012 .88889)" class="t_zwr_bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:es-ct-4x3" /></template>
