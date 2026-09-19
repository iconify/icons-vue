<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkqudab6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkqudab6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:dumbbell" /></template>
