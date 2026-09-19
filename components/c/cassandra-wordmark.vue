<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m52mwjdue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m52mwjdue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:cassandra-wordmark" /></template>
