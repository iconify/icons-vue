<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w33y4mbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w33y4mbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:center-focus-strong-filled" /></template>
