<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lthpuj_eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lthpuj_eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:cursor-o" /></template>
