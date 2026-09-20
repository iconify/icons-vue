<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi857sb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi857sb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-left-square-filled" /></template>
