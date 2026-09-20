<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmyl__bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmyl__bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-pull-request-fill" /></template>
