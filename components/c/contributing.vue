<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu_4-ac5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu_4-ac5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:contributing" /></template>
