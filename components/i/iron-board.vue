<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar1kdeb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar1kdeb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:iron-board" /></template>
