<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4h4sqbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4h4sqbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:libreofficebase" /></template>
