<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl5p5ob0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xl5p5ob0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-php-thin" /></template>
