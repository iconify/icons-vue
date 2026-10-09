<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrwndsbwa.css';
import '../../css/e/ea6-embbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wrwndsbwa"/><path class="ea6-embbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-bottle-20-bold" /></template>
