<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzlpzy4cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzlpzy4cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bag-personal-off-outline" /></template>
