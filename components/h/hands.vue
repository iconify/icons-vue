<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlpmhkb0y.css';
import '../../css/a/arjp9mitp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="mlpmhkb0y"/><path class="arjp9mitp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:hands" /></template>
