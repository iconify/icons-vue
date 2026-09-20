<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo6egfo-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xo6egfo-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:ellipsis-circle" /></template>
