<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6s60-s9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":819,"height":622};
const content = `<path class="w6s60-s9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:friend" /></template>
