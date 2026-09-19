<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef6n7ybih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ef6n7ybih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:faunadb-wordmark" /></template>
