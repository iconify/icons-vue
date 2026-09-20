<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpetjwbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpetjwbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-right" /></template>
