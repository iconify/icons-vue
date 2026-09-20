<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p15fsdbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p15fsdbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:edit" /></template>
