<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5_sz-bgs.css';
import '../../css/b/b86mn5bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p5_sz-bgs"/><path class="b86mn5bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bridge-20-bold" /></template>
