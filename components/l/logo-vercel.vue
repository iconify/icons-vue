<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq8l11ltu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pq8l11ltu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-vercel" /></template>
