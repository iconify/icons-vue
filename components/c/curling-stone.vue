<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovp2cqbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ovp2cqbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:curling-stone" /></template>
