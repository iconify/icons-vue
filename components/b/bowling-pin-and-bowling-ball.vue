<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhbr0d30n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dhbr0d30n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bowling-pin-and-bowling-ball" /></template>
