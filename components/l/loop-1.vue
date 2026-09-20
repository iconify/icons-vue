<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt5lhvbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xt5lhvbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:loop-1" /></template>
