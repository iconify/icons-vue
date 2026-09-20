<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovkd8pb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ovkd8pb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:exclamation-circle" /></template>
