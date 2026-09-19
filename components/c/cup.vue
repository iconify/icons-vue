<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3bj926tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o3bj926tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:cup" /></template>
