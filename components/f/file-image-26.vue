<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7q2z9dzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":26};
const content = `<path class="i7q2z9dzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-image-26" /></template>
