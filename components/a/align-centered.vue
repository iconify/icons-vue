<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1yw06b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":448};
const content = `<path class="h1yw06b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:align-centered" /></template>
