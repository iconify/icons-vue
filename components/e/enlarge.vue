<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4y8jsbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4y8jsbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:enlarge" /></template>
