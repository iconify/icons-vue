<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuo0z1gmg.css';
import '../../css/h/hk7ioiexi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cuo0z1gmg"/><path class="hk7ioiexi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:glasses-20-bold" /></template>
