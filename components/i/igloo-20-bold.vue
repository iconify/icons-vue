<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4fxe_2wu.css';
import '../../css/q/qb-anoa-e.css';
import '../../css/f/fxwh4ibmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g4fxe_2wu"/><path class="qb-anoa-e"/><path class="fxwh4ibmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:igloo-20-bold" /></template>
