<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2jl4nb0t.css';
import '../../css/z/zikzdnbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c2jl4nb0t"/><path class="zikzdnbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brine-pond-20" /></template>
