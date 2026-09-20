<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g581yabrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g581yabrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-3-line" /></template>
