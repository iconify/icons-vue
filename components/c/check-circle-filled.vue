<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1gmc4l8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1gmc4l8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:check-circle-filled" /></template>
