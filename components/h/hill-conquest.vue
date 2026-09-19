<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjiax_43i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rjiax_43i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hill-conquest" /></template>
