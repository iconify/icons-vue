<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyj4tfarm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1046.16,"height":1000};
const content = `<path class="oyj4tfarm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:linkedin" /></template>
