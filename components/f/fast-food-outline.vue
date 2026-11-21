<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9k1c_ucr.css';
import '../../css/r/rkglh0mnh.css';
import '../../css/i/itkvrn4ca.css';
import '../../css/l/l0t-gpb8d.css';
import '../../css/y/yza2inbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u9k1c_ucr"/><path class="rkglh0mnh"/><path class="itkvrn4ca"/><path class="l0t-gpb8d"/><path class="yza2inbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:fast-food-outline" /></template>
