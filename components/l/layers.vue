<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drzgnvcov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="drzgnvcov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:layers" /></template>
