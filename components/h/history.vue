<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j335ufbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="j335ufbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:history" /></template>
