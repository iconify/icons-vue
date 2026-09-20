<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flu3cfv5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="flu3cfv5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:filter" /></template>
