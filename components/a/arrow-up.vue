<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adel1pq3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="adel1pq3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:arrow-up" /></template>
