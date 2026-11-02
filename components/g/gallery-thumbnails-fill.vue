<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q46im1cui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q46im1cui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gallery-thumbnails-fill" /></template>
