<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9ki49b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y9ki49b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:key" /></template>
