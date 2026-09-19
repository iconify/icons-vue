<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwq9ehguz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cwq9ehguz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:circle-with-minus" /></template>
