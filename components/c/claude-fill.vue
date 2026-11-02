<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emplgbbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emplgbbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:claude-fill" /></template>
