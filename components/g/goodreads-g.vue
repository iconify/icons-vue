<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqom6bjey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="hqom6bjey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:goodreads-g" /></template>
