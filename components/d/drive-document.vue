<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z801zl0-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z801zl0-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:drive-document" /></template>
