<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy-ibbztw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy-ibbztw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:album-fill" /></template>
