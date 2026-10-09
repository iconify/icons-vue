<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvo2ojb3s.css';
import '../../css/h/hhfof8-2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kvo2ojb3s"/><path class="hhfof8-2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:croissant-20-bold" /></template>
