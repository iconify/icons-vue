<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nczf9obkd.css';
import '../../css/c/c-s7-tb1l.css';
import '../../css/f/f3r1kpbwq.css';
import '../../css/d/dagi9acwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nczf9obkd"/><path class="c-s7-tb1l"/><path class="f3r1kpbwq"/><path class="dagi9acwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crimper-20-bold" /></template>
