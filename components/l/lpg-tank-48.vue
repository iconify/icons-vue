<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5bjig3qg.css';
import '../../css/w/w9ts85b5q.css';
import '../../css/o/of5hjbcyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c5bjig3qg"/><path class="w9ts85b5q"/><path class="of5hjbcyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lpg-tank-48" /></template>
