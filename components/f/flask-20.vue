<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvlujqvom.css';
import '../../css/o/o6vqyfbqf.css';
import '../../css/t/tks4l1bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kvlujqvom"/><path class="o6vqyfbqf"/><path class="tks4l1bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flask-20" /></template>
