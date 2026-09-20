<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iofa59b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iofa59b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:backwards" /></template>
