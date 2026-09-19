<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg1plbboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg1plbboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-notepad" /></template>
