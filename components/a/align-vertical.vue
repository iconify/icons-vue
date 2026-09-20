<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suy8z-box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suy8z-box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:align-vertical" /></template>
