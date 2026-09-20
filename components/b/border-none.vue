<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrq06_bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrq06_bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:border-none" /></template>
