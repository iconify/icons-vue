<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anhhz7k0l.css';
import '../../css/t/tmt5_jlxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="anhhz7k0l"/><path class="tmt5_jlxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fries-20-bold" /></template>
