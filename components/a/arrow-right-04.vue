<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu-85oigi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu-85oigi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-right-04" /></template>
