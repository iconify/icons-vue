<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-vq89wpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-vq89wpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:building-one" /></template>
