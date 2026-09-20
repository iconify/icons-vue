<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkwi5f_-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nkwi5f_-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:blockquote-20-solid" /></template>
