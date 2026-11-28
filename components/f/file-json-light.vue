<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9oef4b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q9oef4b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-json-light" /></template>
