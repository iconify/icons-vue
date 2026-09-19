<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0-l-ecya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1344};
const content = `<path class="f0-l-ecya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:behance" /></template>
