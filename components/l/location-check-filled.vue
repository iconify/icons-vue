<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm4b4se3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm4b4se3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:location-check-filled" /></template>
