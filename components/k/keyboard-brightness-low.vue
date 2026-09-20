<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjjeli3sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjjeli3sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:keyboard-brightness-low" /></template>
