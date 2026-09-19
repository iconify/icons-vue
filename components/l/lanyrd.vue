<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2l7mnbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r2l7mnbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:lanyrd" /></template>
