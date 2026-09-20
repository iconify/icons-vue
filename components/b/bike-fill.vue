<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9-h2tk1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9-h2tk1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bike-fill" /></template>
