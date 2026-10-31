<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibho_3u6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibho_3u6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-letter-t" /></template>
