<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s03c0fb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s03c0fb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:affiliatetheme" /></template>
