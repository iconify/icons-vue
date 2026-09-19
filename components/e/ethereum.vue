<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc3jlxb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc3jlxb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ethereum" /></template>
