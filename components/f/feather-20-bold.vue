<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1rxiyxan.css';
import '../../css/b/b0cpgnbfh.css';
import '../../css/j/jl8htv4va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w1rxiyxan"/><path class="b0cpgnbfh"/><path class="jl8htv4va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:feather-20-bold" /></template>
