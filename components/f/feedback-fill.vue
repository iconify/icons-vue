<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkb-u9edw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkb-u9edw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:feedback-fill" /></template>
