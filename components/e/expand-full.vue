<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-lzoc2ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x-lzoc2ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:expand-full" /></template>
