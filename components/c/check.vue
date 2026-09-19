<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxr9epwfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rxr9epwfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:check" /></template>
