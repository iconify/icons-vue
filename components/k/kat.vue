<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtc54ubii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtc54ubii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kat" /></template>
