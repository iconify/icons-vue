<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6kma3bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p6kma3bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fruit-bowl" /></template>
