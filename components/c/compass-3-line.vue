<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4edxxbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4edxxbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:compass-3-line" /></template>
