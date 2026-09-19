<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re52c97vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="re52c97vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:basketball-fill-12" /></template>
