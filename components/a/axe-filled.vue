<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz39kfbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz39kfbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:axe-filled" /></template>
