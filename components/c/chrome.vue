<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1bbnfl8v.css';
import '../../css/l/l_rrpccbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="z1bbnfl8v"/><path class="l_rrpccbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:chrome" /></template>
