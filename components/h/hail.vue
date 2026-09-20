<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b87w7g1jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b87w7g1jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:hail" /></template>
