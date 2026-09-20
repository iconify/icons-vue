<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw6n93ogd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw6n93ogd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:inbox-all" /></template>
