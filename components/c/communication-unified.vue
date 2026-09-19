<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m-w9b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a0m-w9b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:communication-unified" /></template>
