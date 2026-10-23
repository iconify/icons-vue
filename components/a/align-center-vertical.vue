<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxycs3m1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxycs3m1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-center-vertical" /></template>
