<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mawh58bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mawh58bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-fill" /></template>
