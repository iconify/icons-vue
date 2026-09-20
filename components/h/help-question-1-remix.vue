<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kci8ccoim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kci8ccoim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:help-question-1-remix" /></template>
