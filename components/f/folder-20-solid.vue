<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et4u17bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="et4u17bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-20-solid" /></template>
