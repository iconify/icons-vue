<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbjydlb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qbjydlb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:goland" /></template>
