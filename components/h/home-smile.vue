<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhf3-7eiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhf3-7eiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:home-smile" /></template>
