<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v58u9hbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v58u9hbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:app-window-gloss" /></template>
