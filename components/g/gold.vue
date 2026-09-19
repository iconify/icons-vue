<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqi_23b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nqi_23b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:gold" /></template>
