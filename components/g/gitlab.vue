<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rciwx7bwu.css';
import '../../css/y/ym3jfkbrh.css';
import '../../css/r/rmme9m09l.css';
import '../../css/g/g0h8z3bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rciwx7bwu"/><path class="ym3jfkbrh"/><path class="rmme9m09l"/><path class="g0h8z3bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gitlab" /></template>
