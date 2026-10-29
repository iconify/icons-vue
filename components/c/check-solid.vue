<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqj1cvadj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqj1cvadj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:check-solid" /></template>
