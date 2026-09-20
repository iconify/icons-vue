<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7vrkybqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":10,"left":-1,"top":13};
const content = `<path class="i7vrkybqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:aws-icon" /></template>
