<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq_-j4dud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq_-j4dud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-top-fill" /></template>
