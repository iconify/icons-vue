<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb4dsrbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qb4dsrbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chevron-with-circle-up" /></template>
