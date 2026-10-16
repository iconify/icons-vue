<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi9ifmbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vi9ifmbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:apps-20" /></template>
