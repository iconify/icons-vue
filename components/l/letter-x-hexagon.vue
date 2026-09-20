<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw2lm8b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw2lm8b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-x-hexagon" /></template>
