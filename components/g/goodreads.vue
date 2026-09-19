<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kblqc7b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kblqc7b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:goodreads" /></template>
