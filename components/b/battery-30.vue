<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar5dirryl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar5dirryl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-30" /></template>
