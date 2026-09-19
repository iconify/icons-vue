<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iww3bo28l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iww3bo28l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:base-document-set" /></template>
