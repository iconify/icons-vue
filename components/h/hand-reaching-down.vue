<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/menb0t_lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="menb0t_lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hand-reaching-down" /></template>
