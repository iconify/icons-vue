<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chchrgbld.css';
import '../../css/h/hockizoar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="chchrgbld"/><path class="hockizoar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:akka" /></template>
