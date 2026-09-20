<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-vu94bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-vu94bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:course-filled" /></template>
