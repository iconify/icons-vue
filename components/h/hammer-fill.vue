<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-88ceb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-88ceb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hammer-fill" /></template>
