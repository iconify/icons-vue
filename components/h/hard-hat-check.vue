<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fib0t9bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fib0t9bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hard-hat-check" /></template>
