<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9i_9xbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e9i_9xbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:kubernetes" /></template>
