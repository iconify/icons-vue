<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrkk489mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrkk489mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:favro" /></template>
