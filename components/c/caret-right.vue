<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwjv94nzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwjv94nzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:caret-right" /></template>
