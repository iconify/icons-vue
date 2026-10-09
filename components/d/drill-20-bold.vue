<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp-n21b6g.css';
import '../../css/g/gnaan2b9l.css';
import '../../css/g/gadfch4xe.css';
import '../../css/k/kjg3jgbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cp-n21b6g"/><path class="gnaan2b9l"/><path class="gadfch4xe"/><path class="kjg3jgbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drill-20-bold" /></template>
