<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnmjmj1pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nnmjmj1pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-20" /></template>
