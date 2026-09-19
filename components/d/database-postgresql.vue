<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu0cnftqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wu0cnftqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:database-postgresql" /></template>
