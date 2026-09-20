<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt4qwgb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt4qwgb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:apachedoris" /></template>
