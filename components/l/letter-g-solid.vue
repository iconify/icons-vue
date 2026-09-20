<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd-cpmb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd-cpmb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-g-solid" /></template>
