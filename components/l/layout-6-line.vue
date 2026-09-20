<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6om7i3xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6om7i3xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-6-line" /></template>
