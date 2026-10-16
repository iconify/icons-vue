<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq_n0i1md.css';
import '../../css/h/hjm-ymvbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qq_n0i1md"/><path class="hjm-ymvbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:control-rod-20" /></template>
