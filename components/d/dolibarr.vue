<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvdoi3b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvdoi3b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dolibarr" /></template>
