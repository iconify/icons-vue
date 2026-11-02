<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la-9fub_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la-9fub_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:key-2-fill" /></template>
