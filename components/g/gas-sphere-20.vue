<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whusgz6dz.css';
import '../../css/t/tx1qmhbzi.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="whusgz6dz"/><path class="tx1qmhbzi"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-sphere-20" /></template>
