<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8lpahleh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8lpahleh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drizzle-line" /></template>
