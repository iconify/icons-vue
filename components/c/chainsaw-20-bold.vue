<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyhy5lb0z.css';
import '../../css/c/cxf3gybkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gyhy5lb0z"/><path class="cxf3gybkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chainsaw-20-bold" /></template>
