<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erh4ajb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erh4ajb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:global-off-fill" /></template>
