<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vitytfb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vitytfb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:clockify" /></template>
