<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um9jo7bca.css';
import '../../css/r/r5ivvvbes.css';
import '../../css/g/gj6i34ybh.css';
import '../../css/c/c49ot4bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="um9jo7bca"/><path class="r5ivvvbes"/><path class="gj6i34ybh"/><path class="c49ot4bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ambulance-20" /></template>
