<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmog9oz3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bmog9oz3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:hammer" /></template>
