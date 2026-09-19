<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv1t2xe7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cv1t2xe7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:align-bottom" /></template>
