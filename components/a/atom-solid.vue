<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mtg81v63p.css';
import '../../css/j/jgcif9d1i.css';
import '../../css/t/txeflkg9t.css';
import '../../css/l/l-ujagxqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mtg81v63p"/><path class="jgcif9d1i"/><path clip-rule="evenodd" class="txeflkg9t"/><path class="l-ujagxqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:atom-solid" /></template>
