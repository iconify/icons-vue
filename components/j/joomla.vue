<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6b8qwb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="c6b8qwb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:joomla" /></template>
