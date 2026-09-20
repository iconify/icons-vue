<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/som0vccsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="som0vccsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:flask" /></template>
