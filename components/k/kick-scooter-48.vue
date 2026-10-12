<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amb3slunr.css';
import '../../css/p/prn6stb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="amb3slunr"/><path class="prn6stb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kick-scooter-48" /></template>
