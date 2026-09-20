<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8edzfyqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8edzfyqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:instagram-light" /></template>
