<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4jy4ac-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="o4jy4ac-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:layout-window-1" /></template>
