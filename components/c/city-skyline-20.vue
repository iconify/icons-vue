<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_wx6iigs.css';
import '../../css/h/hh85jcb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n_wx6iigs"/><path class="hh85jcb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:city-skyline-20" /></template>
