<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h53r0d9bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h53r0d9bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:expand" /></template>
