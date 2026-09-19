<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvw60zv3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvw60zv3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-html" /></template>
