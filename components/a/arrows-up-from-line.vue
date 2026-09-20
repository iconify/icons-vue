<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8jkrnyns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8jkrnyns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrows-up-from-line" /></template>
