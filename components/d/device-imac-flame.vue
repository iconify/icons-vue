<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yil_n-e-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yil_n-e-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-flame" /></template>
