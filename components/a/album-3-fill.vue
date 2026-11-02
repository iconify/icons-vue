<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s01ctnr_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s01ctnr_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:album-3-fill" /></template>
