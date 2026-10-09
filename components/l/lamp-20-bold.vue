<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhbboj22q.css';
import '../../css/a/a8ccsebhs.css';
import '../../css/m/mivqt5bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xhbboj22q"/><path class="a8ccsebhs"/><path class="mivqt5bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lamp-20-bold" /></template>
