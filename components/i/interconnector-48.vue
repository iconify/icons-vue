<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-vml9bmf.css';
import '../../css/j/j8fkx09kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z-vml9bmf"/><path class="j8fkx09kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:interconnector-48" /></template>
