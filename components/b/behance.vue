<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm6vebhwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="gm6vebhwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:behance" /></template>
