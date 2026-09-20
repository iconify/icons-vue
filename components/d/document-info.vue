<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiwb4upak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiwb4upak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:document-info" /></template>
