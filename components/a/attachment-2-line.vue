<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj5ih3bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj5ih3bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:attachment-2-line" /></template>
