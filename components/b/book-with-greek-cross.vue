<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9iqw6b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z9iqw6b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-greek-cross" /></template>
