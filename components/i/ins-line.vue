<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izqo2de1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izqo2de1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ins-line" /></template>
