<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhdij880v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xhdij880v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:column-insert" /></template>
