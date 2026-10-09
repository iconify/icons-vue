<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u47_4yu8m.css';
import '../../css/o/oiw__zvyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u47_4yu8m"/><path class="oiw__zvyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-minus-20-bold" /></template>
