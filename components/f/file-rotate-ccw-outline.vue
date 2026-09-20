<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpwsafsix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpwsafsix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-rotate-ccw-outline" /></template>
