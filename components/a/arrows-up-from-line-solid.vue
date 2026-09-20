<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru1o54b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru1o54b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrows-up-from-line-solid" /></template>
