<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emplo6mir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emplo6mir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:book-fill" /></template>
