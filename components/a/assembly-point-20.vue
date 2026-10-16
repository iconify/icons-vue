<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8mmrwm7a.css';
import '../../css/f/f0p1l589y.css';
import '../../css/a/a_f3to3sd.css';
import '../../css/f/fa51h8hra.css';
import '../../css/i/iz9mkubns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c8mmrwm7a"/><path class="f0p1l589y"/><path class="a_f3to3sd"/><path class="fa51h8hra"/><path class="iz9mkubns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:assembly-point-20" /></template>
