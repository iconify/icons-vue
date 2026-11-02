<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwyr5yfgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwyr5yfgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bell-plus-fill" /></template>
