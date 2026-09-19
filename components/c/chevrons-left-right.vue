<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0ipribch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0ipribch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chevrons-left-right" /></template>
