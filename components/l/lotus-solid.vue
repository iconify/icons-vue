<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_u4t2b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_u4t2b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:lotus-solid" /></template>
