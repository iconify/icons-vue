<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id9bk0b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="id9bk0b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-stroke-12" /></template>
