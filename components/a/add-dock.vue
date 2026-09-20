<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8y6igb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x8y6igb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:add-dock" /></template>
