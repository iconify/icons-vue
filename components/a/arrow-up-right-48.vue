<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uspm4fblj.css';
import '../../css/c/c4gyc8b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uspm4fblj"/><path class="c4gyc8b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-right-48" /></template>
