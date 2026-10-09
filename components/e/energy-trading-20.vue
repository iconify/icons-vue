<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu-l-lbvx.css';
import '../../css/g/g0t4uwbww.css';
import '../../css/c/c7ecv3bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hu-l-lbvx"/><path class="g0t4uwbww"/><path class="c7ecv3bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-trading-20" /></template>
