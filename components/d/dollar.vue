<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2kcggbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c2kcggbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:dollar" /></template>
