<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db9zpw_db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db9zpw_db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:list-box" /></template>
