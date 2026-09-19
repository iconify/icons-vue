<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujf0-3dpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujf0-3dpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:app-store" /></template>
