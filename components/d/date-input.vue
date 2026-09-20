<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mut1umbgi.css';
import '../../css/g/g3-s662on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mut1umbgi"/><path class="g3-s662on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:date-input" /></template>
