<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v532zufdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v532zufdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:grass-in-water" /></template>
