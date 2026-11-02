<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qok4bxvwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qok4bxvwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:incognito-mode-fill" /></template>
