<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1qx-j91i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1qx-j91i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:comment-2-line" /></template>
