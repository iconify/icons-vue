<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq5-61b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jq5-61b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:boeing" /></template>
