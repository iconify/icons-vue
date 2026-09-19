<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epi4yab0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="epi4yab0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:firebase" /></template>
