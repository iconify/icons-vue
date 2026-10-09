<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6wbwjb8t.css';
import '../../css/x/xxkd03eis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f6wbwjb8t"/><path class="xxkd03eis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:book-48-bold" /></template>
