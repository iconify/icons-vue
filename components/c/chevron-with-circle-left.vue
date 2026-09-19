<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7h3fsbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h7h3fsbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chevron-with-circle-left" /></template>
