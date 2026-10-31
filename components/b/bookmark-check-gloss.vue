<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey3ifmspw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey3ifmspw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bookmark-check-gloss" /></template>
