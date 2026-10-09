<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4-t3sb5t.css';
import '../../css/y/y8hh19bpj.css';
import '../../css/j/j5eu97tgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w4-t3sb5t"/><path class="y8hh19bpj"/><path class="j5eu97tgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kpi-20-bold" /></template>
