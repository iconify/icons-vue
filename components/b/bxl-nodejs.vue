<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar9d4uk4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar9d4uk4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-nodejs" /></template>
