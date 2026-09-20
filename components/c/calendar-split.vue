<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj1cvqbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="nj1cvqbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:calendar-split" /></template>
