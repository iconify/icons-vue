<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2pgv4bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16.2};
const content = `<path class="q2pgv4bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:altumptic" /></template>
