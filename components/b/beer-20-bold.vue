<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr0t6xbmu.css';
import '../../css/h/hviuulbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yr0t6xbmu"/><path class="hviuulbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:beer-20-bold" /></template>
