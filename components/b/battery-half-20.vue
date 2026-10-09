<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkwocjb5q.css';
import '../../css/h/hhg2zab-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mkwocjb5q"/><path class="hhg2zab-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-half-20" /></template>
