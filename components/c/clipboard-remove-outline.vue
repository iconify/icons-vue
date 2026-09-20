<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5ymm7dfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5ymm7dfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-remove-outline" /></template>
