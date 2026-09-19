<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvdt7r95i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="hvdt7r95i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:github-box" /></template>
