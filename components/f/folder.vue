<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc-660lro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc-660lro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:folder" /></template>
