<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc0d_ubzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":832};
const content = `<path class="fc0d_ubzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:github" /></template>
