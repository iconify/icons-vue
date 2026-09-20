<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai40zdbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai40zdbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-arrow-right-line" /></template>
