<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6ulymbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="w6ulymbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:caret-square-down" /></template>
