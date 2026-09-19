<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8wc5t8ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="g8wc5t8ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:chevron-left" /></template>
