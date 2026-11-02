<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwp56obhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwp56obhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-plus-line" /></template>
