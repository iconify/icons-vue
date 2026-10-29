<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgo5kz4zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgo5kz4zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-right-duo" /></template>
