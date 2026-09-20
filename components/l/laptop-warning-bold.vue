<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_ggsobwy.css';
import '../../css/g/gxkm953bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_ggsobwy"/><path class="gxkm953bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:laptop-warning-bold" /></template>
