<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mamb4q5gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mamb4q5gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:backspace-a" /></template>
