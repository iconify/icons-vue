<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys7-5437z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys7-5437z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:blocks-filled" /></template>
