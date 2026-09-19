<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqhp6dbju.css';
import '../../css/p/pzbcwvb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kqhp6dbju"/><path class="pzbcwvb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-heart-filled" /></template>
