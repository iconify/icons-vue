<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg9elfixr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg9elfixr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:clipboard-line" /></template>
