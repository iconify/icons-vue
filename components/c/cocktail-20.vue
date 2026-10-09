<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g63ekpb2v.css';
import '../../css/m/mq8znxbqs.css';
import '../../css/u/u5dr5zbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g63ekpb2v"/><path class="mq8znxbqs"/><path class="u5dr5zbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cocktail-20" /></template>
