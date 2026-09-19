<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2kh23b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="v2kh23b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:filter" /></template>
