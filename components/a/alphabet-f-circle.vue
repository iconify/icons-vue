<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7kwija_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7kwija_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-f-circle" /></template>
