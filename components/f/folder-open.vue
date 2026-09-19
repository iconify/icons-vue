<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcpo-bbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hcpo-bbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:folder-open" /></template>
