<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q18dlc9vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q18dlc9vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-search" /></template>
