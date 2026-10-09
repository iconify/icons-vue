<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvmjd2aub.css';
import '../../css/f/f6d284boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pvmjd2aub"/><path class="f6d284boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cylinder-20-bold" /></template>
