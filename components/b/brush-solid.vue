<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i82r32b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i82r32b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:brush-solid" /></template>
