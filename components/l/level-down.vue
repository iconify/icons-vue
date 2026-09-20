<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb-umtbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rb-umtbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:level-down" /></template>
