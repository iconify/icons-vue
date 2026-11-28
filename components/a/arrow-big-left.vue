<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-xvnsbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-xvnsbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrow-big-left" /></template>
