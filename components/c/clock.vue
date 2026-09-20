<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaye1ubvf.css';
import '../../css/e/ej6vge06z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uaye1ubvf"/><path class="ej6vge06z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:clock" /></template>
