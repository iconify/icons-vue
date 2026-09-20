<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljclpqbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ljclpqbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:loop-square" /></template>
