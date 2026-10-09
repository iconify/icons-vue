<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiwfi4b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aiwfi4b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-steel-20" /></template>
