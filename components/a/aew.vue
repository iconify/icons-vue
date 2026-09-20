<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa2d_wzze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa2d_wzze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:aew" /></template>
