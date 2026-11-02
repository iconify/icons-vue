<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huucxrbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huucxrbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:infinity-2-fill" /></template>
