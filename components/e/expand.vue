<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3qesqo9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="d3qesqo9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:expand" /></template>
