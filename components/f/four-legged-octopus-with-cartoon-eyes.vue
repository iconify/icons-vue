<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py1y6o2db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="py1y6o2db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:four-legged-octopus-with-cartoon-eyes" /></template>
