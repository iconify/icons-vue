<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha0nppz8t.css';
import '../../css/h/hhk88wzsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ha0nppz8t"/><path class="hhk88wzsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-text" /></template>
