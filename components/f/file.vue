<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9sg1poyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m9sg1poyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file" /></template>
