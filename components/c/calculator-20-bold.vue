<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp1n75bba.css';
import '../../css/o/osbs8kx0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pp1n75bba"/><path class="osbs8kx0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calculator-20-bold" /></template>
