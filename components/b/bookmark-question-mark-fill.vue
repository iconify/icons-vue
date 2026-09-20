<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn6ghm8vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn6ghm8vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bookmark-question-mark-fill" /></template>
