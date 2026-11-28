<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6tgntbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6tgntbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gate-buffer-solid" /></template>
