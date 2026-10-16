<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e75-znlde.css';
import '../../css/m/mx7qgn1xx.css';
import '../../css/q/qviq0ilhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e75-znlde"/><path class="mx7qgn1xx"/><path class="qviq0ilhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-gauge-20-bold" /></template>
