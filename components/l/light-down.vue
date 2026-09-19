<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0ii90bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0ii90bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:light-down" /></template>
