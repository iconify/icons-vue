<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p85hodb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p85hodb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrow-backward" /></template>
