<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9y2hdich.css';
import '../../css/m/maibb9b4m.css';
import '../../css/g/g9fwkabiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j9y2hdich"/><path class="maibb9b4m"/><path class="g9fwkabiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-hydrogen-20-bold" /></template>
