<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa5wd-b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa5wd-b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-star" /></template>
