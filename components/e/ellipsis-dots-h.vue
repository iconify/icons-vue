<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx1qguu2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gx1qguu2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:ellipsis-dots-h" /></template>
