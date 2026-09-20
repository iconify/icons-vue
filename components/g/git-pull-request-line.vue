<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcolw39jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcolw39jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-pull-request-line" /></template>
