<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvvrh6fwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cvvrh6fwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:edit-contact" /></template>
