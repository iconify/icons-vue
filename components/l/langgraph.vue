<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrnl9w13i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrnl9w13i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:langgraph" /></template>
