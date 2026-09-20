<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm1d98grv.css';
import '../../css/r/rgiy7zbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lm1d98grv"/><path class="rgiy7zbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:flip-v" /></template>
