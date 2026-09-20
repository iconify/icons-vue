<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-k45ob-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s-k45ob-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:apple" /></template>
