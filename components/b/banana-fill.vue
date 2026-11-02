<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hczh8rbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hczh8rbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:banana-fill" /></template>
