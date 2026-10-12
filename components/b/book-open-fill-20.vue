<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2a06bc3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g2a06bc3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-open-fill-20" /></template>
