<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v47oox13y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v47oox13y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:headphones" /></template>
