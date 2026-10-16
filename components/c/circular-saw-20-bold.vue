<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot0mghbfc.css';
import '../../css/j/jwxwoobeu.css';
import '../../css/e/etrl1rckl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ot0mghbfc"/><path class="jwxwoobeu"/><path class="etrl1rckl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:circular-saw-20-bold" /></template>
