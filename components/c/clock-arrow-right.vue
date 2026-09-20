<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyxhi1qlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyxhi1qlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-arrow-right" /></template>
