<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_huerbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_huerbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:logout-2" /></template>
