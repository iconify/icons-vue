<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8e9dnbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8e9dnbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:error-triangle-filled" /></template>
