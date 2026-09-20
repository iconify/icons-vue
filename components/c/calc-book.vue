<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dadjwxblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dadjwxblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:calc-book" /></template>
