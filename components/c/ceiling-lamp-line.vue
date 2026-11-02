<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gquns0ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gquns0ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ceiling-lamp-line" /></template>
