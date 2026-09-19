<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8_0mf2my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8_0mf2my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:cursor" /></template>
