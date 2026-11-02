<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akimx7bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akimx7bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-ordered-line" /></template>
