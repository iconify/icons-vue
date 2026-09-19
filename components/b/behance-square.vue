<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c65qsgblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="c65qsgblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:behance-square" /></template>
