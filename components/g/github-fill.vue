<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqxt5mdob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqxt5mdob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:github-fill" /></template>
