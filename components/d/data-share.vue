<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9ne0ef5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v9ne0ef5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-share" /></template>
