<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za9qyur9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1280};
const content = `<path class="za9qyur9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrows-h" /></template>
