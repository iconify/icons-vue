<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axj-rzbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axj-rzbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-remove" /></template>
