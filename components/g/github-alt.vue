<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf9hn5q-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="cf9hn5q-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:github-alt" /></template>
