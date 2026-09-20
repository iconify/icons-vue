<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlyhh3nbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rlyhh3nbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:exit" /></template>
