<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnn6srcuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnn6srcuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-exclamation" /></template>
