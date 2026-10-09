<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjz8wn-my.css';
import '../../css/u/ukun5-bzx.css';
import '../../css/p/p5wu9x5yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tjz8wn-my"/><path class="ukun5-bzx"/><path class="p5wu9x5yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-flexibility-20" /></template>
