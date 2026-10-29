<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2lk7zboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2lk7zboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud" /></template>
