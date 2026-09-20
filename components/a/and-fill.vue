<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng0uscbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng0uscbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:and-fill" /></template>
