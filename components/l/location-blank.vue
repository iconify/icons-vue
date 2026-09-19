<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msf35150p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msf35150p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:location-blank" /></template>
