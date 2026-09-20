<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2dngh0fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j2dngh0fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:feedback-rtl" /></template>
