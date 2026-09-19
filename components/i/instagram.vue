<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj5j7fs1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tj5j7fs1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:instagram" /></template>
