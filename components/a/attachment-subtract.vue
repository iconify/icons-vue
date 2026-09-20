<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pimuhx55s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pimuhx55s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:attachment-subtract" /></template>
