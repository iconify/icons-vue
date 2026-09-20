<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgzi01biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgzi01biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-star" /></template>
