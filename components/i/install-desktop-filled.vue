<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5fihgbly.css';
import '../../css/n/npbkqyb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5fihgbly"/><path class="npbkqyb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:install-desktop-filled" /></template>
