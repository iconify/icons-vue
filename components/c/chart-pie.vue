<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayw6rtddd.css';
import '../../css/e/e-psi4b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ayw6rtddd"/><path class="e-psi4b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:chart-pie" /></template>
