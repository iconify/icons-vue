<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to0c2ub7t.css';
import '../../css/p/pxigoteko.css';
import '../../css/n/n0z6nacxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="to0c2ub7t"><path clip-rule="evenodd" class="pxigoteko"/><path class="n0z6nacxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:enter" /></template>
