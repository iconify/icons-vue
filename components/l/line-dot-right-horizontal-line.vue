<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgngm0alo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgngm0alo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:line-dot-right-horizontal-line" /></template>
