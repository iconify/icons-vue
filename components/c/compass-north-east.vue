<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1guqyk7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="h1guqyk7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:compass-north-east" /></template>
