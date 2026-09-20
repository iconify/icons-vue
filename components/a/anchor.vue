<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4im118es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z4im118es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:anchor" /></template>
