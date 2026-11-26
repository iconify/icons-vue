<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jea36wsph.css';
import '../../css/t/tep7rtb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":156,"top":316.5};
const content = `<path class="jea36wsph"/><path class="tep7rtb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:anadolujet" /></template>
