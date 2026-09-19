<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekp8m2b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekp8m2b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-basketball" /></template>
