<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-7xz0k4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-7xz0k4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:folder" /></template>
