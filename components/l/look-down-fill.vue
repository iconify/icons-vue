<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayiptbb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayiptbb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:look-down-fill" /></template>
