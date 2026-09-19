<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muo_u7brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muo_u7brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-download" /></template>
