<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ongdct72a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ongdct72a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-text-fill" /></template>
