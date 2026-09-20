<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_tmx52z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca_tmx52z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-aurebesh" /></template>
