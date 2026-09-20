<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjpb8vtki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjpb8vtki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-up-left" /></template>
