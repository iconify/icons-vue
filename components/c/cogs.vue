<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgj2zbb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sgj2zbb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cogs" /></template>
