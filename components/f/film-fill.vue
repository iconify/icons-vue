<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yihsg2t7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yihsg2t7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:film-fill" /></template>
