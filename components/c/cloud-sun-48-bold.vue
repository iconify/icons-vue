<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vubs4oo9h.css';
import '../../css/c/cohq8848r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vubs4oo9h"/><path class="cohq8848r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sun-48-bold" /></template>
