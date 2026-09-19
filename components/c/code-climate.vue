<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfun62owm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfun62owm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:code-climate" /></template>
