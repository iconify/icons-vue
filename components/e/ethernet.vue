<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl5l6ibkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl5l6ibkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ethernet" /></template>
