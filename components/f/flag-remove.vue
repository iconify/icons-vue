<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsrio4bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsrio4bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-remove" /></template>
