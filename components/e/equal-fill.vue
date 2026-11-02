<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb7-6ib7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb7-6ib7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:equal-fill" /></template>
