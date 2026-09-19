<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqievacsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":718,"height":694};
const content = `<path class="pqievacsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:arrowup" /></template>
