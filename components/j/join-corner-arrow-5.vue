<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7vk71b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y7vk71b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:join-corner-arrow-5" /></template>
