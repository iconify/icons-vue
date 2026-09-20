<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sojm5tbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sojm5tbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:glass-cup-fill" /></template>
