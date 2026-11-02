<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6fn8xqie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6fn8xqie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:blockquote-line" /></template>
