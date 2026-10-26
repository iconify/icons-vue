<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1bjk9b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h1bjk9b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:library" /></template>
