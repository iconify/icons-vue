<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfc3j7wuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfc3j7wuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heartbeat-line" /></template>
