<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_1lwukaz.css';
import '../../css/g/gandzumwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p_1lwukaz"/><path class="gandzumwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:graduation-cap-20" /></template>
