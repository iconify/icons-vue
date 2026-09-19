<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr18iotvw.css';
import '../../css/d/dxd4apb8s.css';
import '../../css/o/ol-mkhbiz.css';
import '../../css/r/r97skqbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="zr18iotvw"/><path class="dxd4apb8s"/><path class="ol-mkhbiz"/><path class="r97skqbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:launch-study-2" /></template>
