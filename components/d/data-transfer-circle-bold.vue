<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rob-vnojp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rob-vnojp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:data-transfer-circle-bold" /></template>
