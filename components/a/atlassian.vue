<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1qjz2bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f1qjz2bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:atlassian" /></template>
