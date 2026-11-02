<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvicvcb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvicvcb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:columns-3-fill" /></template>
