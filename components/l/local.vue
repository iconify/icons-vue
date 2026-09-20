<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxlnq_1on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxlnq_1on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:local" /></template>
