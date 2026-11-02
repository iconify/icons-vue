<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id_vwwy8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id_vwwy8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-up-right-line" /></template>
