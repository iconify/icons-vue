<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytj3n3bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytj3n3bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-right-line" /></template>
