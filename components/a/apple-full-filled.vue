<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms7wlk1xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms7wlk1xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:apple-full-filled" /></template>
