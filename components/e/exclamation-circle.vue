<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daobr4a-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="daobr4a-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:exclamation-circle" /></template>
