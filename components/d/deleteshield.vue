<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_fu2bbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="d_fu2bbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:deleteshield" /></template>
