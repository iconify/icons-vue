<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl2-kobue.css';
import '../../css/n/n93i43b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jl2-kobue"/><path class="n93i43b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:dotnetcore" /></template>
