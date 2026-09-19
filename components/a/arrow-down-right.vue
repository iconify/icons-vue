<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7x-4mbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d7x-4mbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-down-right" /></template>
