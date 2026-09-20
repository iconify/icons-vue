<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nucn65bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nucn65bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-heart" /></template>
