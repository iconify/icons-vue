<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsku-rbch.css';
import '../../css/i/in_k0mbzy.css';
import '../../css/d/dc6crytza.css';
import '../../css/m/mndorw7al.css';
import '../../css/c/caf4nbbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vsku-rbch"/><path class="in_k0mbzy"/><path class="dc6crytza"/><path class="mndorw7al"/><path class="caf4nbbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:floating-wind-20-bold" /></template>
