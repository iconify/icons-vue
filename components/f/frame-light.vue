<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucmw7d4mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucmw7d4mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:frame-light" /></template>
