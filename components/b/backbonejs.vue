<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb3dx9ovg.css';
import '../../css/o/o68ncmbqz.css';
import '../../css/u/uw85bc0ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xb3dx9ovg"/><path class="o68ncmbqz"/><path class="uw85bc0ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:backbonejs" /></template>
