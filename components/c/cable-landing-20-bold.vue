<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag0bvbcgf.css';
import '../../css/g/gampl1_hh.css';
import '../../css/b/b0z-l4tfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ag0bvbcgf"/><path class="gampl1_hh"/><path class="b0z-l4tfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-landing-20-bold" /></template>
