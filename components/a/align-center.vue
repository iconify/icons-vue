<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k383-3bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k383-3bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:align-center" /></template>
