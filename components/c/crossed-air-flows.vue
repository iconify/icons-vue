<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3qs2xnju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l3qs2xnju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crossed-air-flows" /></template>
