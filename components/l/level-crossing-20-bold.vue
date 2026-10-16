<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr770pz-q.css';
import '../../css/o/orx0-2epj.css';
import '../../css/s/sbh9h8-ru.css';
import '../../css/s/s4owz8l_h.css';
import '../../css/p/p804tzuwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gr770pz-q"/><path class="orx0-2epj"/><path class="sbh9h8-ru"/><path class="s4owz8l_h"/><path class="p804tzuwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:level-crossing-20-bold" /></template>
