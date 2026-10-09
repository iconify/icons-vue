<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4es65b1e.css';
import '../../css/f/f1nb5abut.css';
import '../../css/s/spc7yovzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q4es65b1e"/><path class="f1nb5abut"/><path class="spc7yovzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-train-20" /></template>
