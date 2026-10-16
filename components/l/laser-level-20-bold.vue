<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7byejq-o.css';
import '../../css/c/c3mb_pbac.css';
import '../../css/p/poj_abb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s7byejq-o"/><path class="c3mb_pbac"/><path class="poj_abb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:laser-level-20-bold" /></template>
