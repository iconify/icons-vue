<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkzyz0b-d.css';
import '../../css/u/u9h8d2d_j.css';
import '../../css/o/oh7fmbq9r.css';
import '../../css/d/d37t4ibym.css';
import '../../css/w/wcxel2c8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gkzyz0b-d"/><path class="u9h8d2d_j"/><path class="oh7fmbq9r"/><path class="d37t4ibym"/><path class="wcxel2c8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fingerprint-recognition" /></template>
