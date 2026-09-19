<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yws5cp5zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yws5cp5zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:logout" /></template>
