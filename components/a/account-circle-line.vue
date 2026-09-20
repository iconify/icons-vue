<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnmvl1dlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnmvl1dlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:account-circle-line" /></template>
