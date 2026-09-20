<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqz4vgzgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqz4vgzgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-down-left-linear" /></template>
