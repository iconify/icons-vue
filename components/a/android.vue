<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx8lp924d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx8lp924d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:android" /></template>
