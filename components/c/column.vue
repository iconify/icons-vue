<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9mx3vn6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o9mx3vn6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:column" /></template>
