<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylj6s1ump.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylj6s1ump"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:lightbulb" /></template>
