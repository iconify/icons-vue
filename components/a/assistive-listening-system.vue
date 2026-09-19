<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjqhxbbwg.css';
import '../../css/g/g6xizdbtb.css';
import '../../css/o/o15x4kbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fjqhxbbwg"/><path class="g6xizdbtb"/><path class="o15x4kbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:assistive-listening-system" /></template>
