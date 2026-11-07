<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xteelq4gg.css';
import '../../css/h/h28ok-b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xteelq4gg"/><path class="h28ok-b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-from-line-bold" /></template>
