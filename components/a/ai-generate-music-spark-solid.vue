<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at-x-4buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="at-x-4buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-generate-music-spark-solid" /></template>
