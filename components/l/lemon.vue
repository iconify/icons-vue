<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh145ccko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jh145ccko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:lemon" /></template>
