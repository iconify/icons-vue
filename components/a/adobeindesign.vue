<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjfbw8b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfbw8b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:adobeindesign" /></template>
