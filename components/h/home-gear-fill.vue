<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg_5v1b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg_5v1b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-gear-fill" /></template>
