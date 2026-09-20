<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2jymg60n.css';
import '../../css/w/w_nq73a6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f2jymg60n"/><path class="w_nq73a6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:hourglass-start" /></template>
