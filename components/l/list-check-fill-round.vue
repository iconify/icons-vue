<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0jc5rbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0jc5rbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-check-fill-round" /></template>
