<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldf7blynr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldf7blynr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:github-line" /></template>
