<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf44fsf2t.css';
import '../../css/f/fy0c3cbja.css';
import '../../css/o/op21zq27n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uf44fsf2t"/><path class="fy0c3cbja"/><path class="op21zq27n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-slow-48-bold" /></template>
