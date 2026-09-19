<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_2-9c3fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s_2-9c3fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-aa" /></template>
