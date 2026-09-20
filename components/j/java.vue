<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zer3fduql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zer3fduql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:java" /></template>
