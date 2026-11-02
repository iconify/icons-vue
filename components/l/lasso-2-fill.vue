<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1143ab2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1143ab2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lasso-2-fill" /></template>
