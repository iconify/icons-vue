<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ingzkbbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ingzkbbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:layer-group" /></template>
