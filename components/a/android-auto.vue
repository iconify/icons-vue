<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caldd_r-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caldd_r-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:android-auto" /></template>
