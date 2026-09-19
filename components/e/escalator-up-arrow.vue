<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg6p6hbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg6p6hbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:escalator-up-arrow" /></template>
