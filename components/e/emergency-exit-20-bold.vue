<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5tyujbpm.css';
import '../../css/l/l3tq00bvz.css';
import '../../css/d/dce81qbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d5tyujbpm"/><path class="l3tq00bvz"/><path class="dce81qbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:emergency-exit-20-bold" /></template>
