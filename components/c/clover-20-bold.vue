<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdw4w6evj.css';
import '../../css/x/xn1pz4iuf.css';
import '../../css/w/w9gsb7blj.css';
import '../../css/h/h1e1mnb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jdw4w6evj"/><path class="xn1pz4iuf"/><path class="w9gsb7blj"/><path class="h1e1mnb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clover-20-bold" /></template>
