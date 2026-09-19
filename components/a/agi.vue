<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj-xp5bcy.css';
import '../../css/y/ym37o3bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mj-xp5bcy"/><path class="ym37o3bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:agi" /></template>
