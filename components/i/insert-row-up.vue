<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rqg21wbtn.css';
import '../../css/h/hbbh8abmi.css';
import '../../css/p/p5f3lmg3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rqg21wbtn"/><path class="hbbh8abmi"/><path class="p5f3lmg3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:insert-row-up" /></template>
