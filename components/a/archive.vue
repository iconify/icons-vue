<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft9sjzb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ft9sjzb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:archive" /></template>
