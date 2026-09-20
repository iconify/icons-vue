<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdggzp0fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cdggzp0fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:envelope-open" /></template>
