<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3vs7td1h.css';
import '../../css/o/o2a1_1bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t3vs7td1h"/><path class="o2a1_1bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bomb" /></template>
