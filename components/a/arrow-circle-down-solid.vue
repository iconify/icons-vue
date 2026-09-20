<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9cm65b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9cm65b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-circle-down-solid" /></template>
