<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0czblbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":472};
const content = `<path class="h0czblbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:amazon" /></template>
