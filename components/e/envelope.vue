<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8zf1xq5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="g8zf1xq5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:envelope" /></template>
