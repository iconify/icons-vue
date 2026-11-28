<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kitaxpzmp.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/te-6n-baq.css';
import '../../css/e/eh8r4ccab.css';
import '../../css/e/e2cr6acpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kitaxpzmp secondary"/><g class="dt0cm9dhy primary"><path class="te-6n-baq"/><path class="eh8r4ccab"/><path class="e2cr6acpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:calculator-duo" /></template>
