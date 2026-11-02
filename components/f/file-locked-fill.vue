<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p584x4bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p584x4bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-locked-fill" /></template>
