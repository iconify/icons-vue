<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po2dz6a3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po2dz6a3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid-filled" /></template>
