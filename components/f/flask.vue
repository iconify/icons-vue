<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh9xdjbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh9xdjbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask" /></template>
