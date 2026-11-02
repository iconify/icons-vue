<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mia6fe8ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mia6fe8ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-certificate-fill" /></template>
